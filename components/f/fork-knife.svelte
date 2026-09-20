<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqh28jm6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqh28jm6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:fork-knife" {...props}></Icon>
