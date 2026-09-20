<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha685db6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ha685db6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-16-solid" {...props}></Icon>
