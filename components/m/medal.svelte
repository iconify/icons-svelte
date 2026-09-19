<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk1t6fbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lk1t6fbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:medal" {...props}></Icon>
