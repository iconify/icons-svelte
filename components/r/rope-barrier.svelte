<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emvy9ge9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="emvy9ge9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:rope-barrier" {...props}></Icon>
