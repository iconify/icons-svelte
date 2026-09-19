<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reejdb5eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":32};
const content = `<path class="reejdb5eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:profile-female" {...props}></Icon>
