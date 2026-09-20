<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm81rxbus.css';
import '../../css/o/otjlhglbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lm81rxbus"/><path class="otjlhglbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:html5-dark" {...props}></Icon>
