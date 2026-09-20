<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_b2bhblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="j_b2bhblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:align-right" {...props}></Icon>
