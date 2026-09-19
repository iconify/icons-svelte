<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o180gvvzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o180gvvzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:american-football" {...props}></Icon>
