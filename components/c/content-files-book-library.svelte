<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7quqgbjv.css';
import '../../css/s/s1tnk0x5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y7quqgbjv"/><path class="s1tnk0x5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-book-library" {...props}></Icon>
