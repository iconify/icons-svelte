<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3gymacee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3gymacee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:plug-24" {...props}></Icon>
