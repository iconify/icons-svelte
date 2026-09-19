<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re34m18fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="re34m18fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-down-right" {...props}></Icon>
