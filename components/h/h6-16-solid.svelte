<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp33byh8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kp33byh8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h6-16-solid" {...props}></Icon>
