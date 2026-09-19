<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz4zr0-dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zz4zr0-dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:envelope-open-16-solid" {...props}></Icon>
