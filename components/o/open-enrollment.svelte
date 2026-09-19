<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enlged6oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="enlged6oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:open-enrollment" {...props}></Icon>
