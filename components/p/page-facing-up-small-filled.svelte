<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp-haacza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="tp-haacza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:page-facing-up-small-filled" {...props}></Icon>
