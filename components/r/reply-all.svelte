<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqa0q9itw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wqa0q9itw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:reply-all" {...props}></Icon>
