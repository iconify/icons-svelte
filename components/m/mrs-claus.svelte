<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adhr84b5i.css';
import '../../css/h/htmu1qfhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="adhr84b5i"/><path class="htmu1qfhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:mrs-claus" {...props}></Icon>
