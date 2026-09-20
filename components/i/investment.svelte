<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9cib2wjc.css';
import '../../css/r/reay3euxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="z9cib2wjc"/><path class="reay3euxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:investment" {...props}></Icon>
