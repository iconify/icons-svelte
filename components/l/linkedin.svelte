<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikpp05bgn.css';
import '../../css/t/ta9uhpgzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikpp05bgn"/><path class="ta9uhpgzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:linkedin" {...props}></Icon>
