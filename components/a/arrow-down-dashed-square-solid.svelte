<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq1of3eyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kq1of3eyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-down-dashed-square-solid" {...props}></Icon>
