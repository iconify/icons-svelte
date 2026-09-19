<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qap3ypbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qap3ypbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-union" {...props}></Icon>
