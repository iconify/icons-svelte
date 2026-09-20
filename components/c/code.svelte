<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85l1hqup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="f85l1hqup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:code" {...props}></Icon>
