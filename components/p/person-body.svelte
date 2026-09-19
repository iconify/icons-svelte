<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vowu4hbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vowu4hbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:person-body" {...props}></Icon>
