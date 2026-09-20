<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilv9ww7ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ilv9ww7ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:computer-outline" {...props}></Icon>
