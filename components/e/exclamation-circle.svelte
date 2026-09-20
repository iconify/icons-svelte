<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2hrgrbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2hrgrbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:exclamation-circle" {...props}></Icon>
