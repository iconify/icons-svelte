<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k00a4g7yc.css';
import '../../css/o/otjvghwvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k00a4g7yc"/><path class="otjvghwvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:application-virtual" {...props}></Icon>
