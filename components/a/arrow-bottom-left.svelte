<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoy1df99u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eoy1df99u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-bottom-left" {...props}></Icon>
