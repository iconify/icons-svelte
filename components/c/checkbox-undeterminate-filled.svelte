<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1ooz0bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m1ooz0bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkbox-undeterminate-filled" {...props}></Icon>
