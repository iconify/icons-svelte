<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh_2lkh4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xh_2lkh4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:infinity" {...props}></Icon>
