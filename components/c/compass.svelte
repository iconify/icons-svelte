<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr1bk8ial.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nr1bk8ial"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:compass" {...props}></Icon>
