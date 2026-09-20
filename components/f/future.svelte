<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrp6a7bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="rrp6a7bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:future" {...props}></Icon>
