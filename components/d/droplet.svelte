<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os4wsf10g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="os4wsf10g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:droplet" {...props}></Icon>
