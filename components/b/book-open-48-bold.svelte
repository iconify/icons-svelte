<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9e918kkq.css';
import '../../css/z/z4lhijw9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9e918kkq"/><path class="z4lhijw9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-open-48-bold" {...props}></Icon>
