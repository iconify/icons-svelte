<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muy8p_6ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="muy8p_6ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:border" {...props}></Icon>
