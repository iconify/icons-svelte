<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/czbk68b1i.css';
import '../../css/a/af7v1pb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="czbk68b1i"/><path class="af7v1pb9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:flower-playing-cards" {...props}></Icon>
