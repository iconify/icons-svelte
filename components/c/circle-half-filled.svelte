<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bavkt7crj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bavkt7crj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:circle-half-filled" {...props}></Icon>
