<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngt43k2ft.css';
import '../../css/h/hi1o7nsyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ngt43k2ft"/><path class="hi1o7nsyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pin" {...props}></Icon>
