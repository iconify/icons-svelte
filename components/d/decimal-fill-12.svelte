<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go9655bbx.css';
import '../../css/y/yqefc5upf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<ellipse class="go9655bbx"/><circle class="yqefc5upf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:decimal-fill-12" {...props}></Icon>
