<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp6h71bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sp6h71bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pump-soap" {...props}></Icon>
