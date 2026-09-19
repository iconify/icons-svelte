<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1ch7ybkg.css';
import '../../css/t/tqb_6nb6c.css';
import '../../css/i/i7jv4xbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="f1ch7ybkg"/><circle class="tqb_6nb6c"/><circle class="i7jv4xbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:more-one" {...props}></Icon>
