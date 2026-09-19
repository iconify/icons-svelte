<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-db58byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o-db58byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:clapping-hands" {...props}></Icon>
