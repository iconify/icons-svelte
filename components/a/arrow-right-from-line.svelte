<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hetb5acfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hetb5acfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-right-from-line" {...props}></Icon>
