<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vukehn95i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vukehn95i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bat" {...props}></Icon>
