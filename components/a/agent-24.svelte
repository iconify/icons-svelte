<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv0mdubqx.css';
import '../../css/q/qgpj5zbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv0mdubqx"/><path class="qgpj5zbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:agent-24" {...props}></Icon>
