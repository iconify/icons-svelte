<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-kw0fbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="x-kw0fbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bug" {...props}></Icon>
