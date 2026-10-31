<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve4cdcoma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ve4cdcoma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h6-16-solid" {...props}></Icon>
