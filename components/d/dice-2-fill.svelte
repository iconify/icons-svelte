<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vropt3bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vropt3bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dice-2-fill" {...props}></Icon>
