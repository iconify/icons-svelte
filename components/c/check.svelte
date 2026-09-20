<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5xg36kjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k5xg36kjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:check" {...props}></Icon>
