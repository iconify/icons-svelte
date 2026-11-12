<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc5njjxlp.css';
import '../../css/b/bjzxtacce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rc5njjxlp"/><path class="bjzxtacce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filegator-dark" {...props}></Icon>
