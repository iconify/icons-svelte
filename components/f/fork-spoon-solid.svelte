<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-eur9bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t-eur9bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fork-spoon-solid" {...props}></Icon>
