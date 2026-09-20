<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm58fobcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pm58fobcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:highway-rest-area" {...props}></Icon>
