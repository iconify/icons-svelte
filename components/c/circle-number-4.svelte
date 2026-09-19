<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6ivl9ats.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v6ivl9ats"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-number-4" {...props}></Icon>
