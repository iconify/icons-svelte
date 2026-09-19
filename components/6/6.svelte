<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojjrbdc4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":781};
const content = `<path class="ojjrbdc4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:6" {...props}></Icon>
