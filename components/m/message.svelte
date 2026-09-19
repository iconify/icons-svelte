<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfj4xhnmo.css';
import '../../css/f/f2-nhmb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rfj4xhnmo"/><path class="f2-nhmb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:message" {...props}></Icon>
