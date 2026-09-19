<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqu4ud82b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tqu4ud82b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pen-nib" {...props}></Icon>
