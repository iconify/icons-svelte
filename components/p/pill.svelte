<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icg1szbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="icg1szbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pill" {...props}></Icon>
