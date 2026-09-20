<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr4-27x8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="kr4-27x8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:lineicons-symbol-alt" {...props}></Icon>
