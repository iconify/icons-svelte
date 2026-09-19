<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh8p9kf-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yh8p9kf-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-uturn-down-circle-fill" {...props}></Icon>
