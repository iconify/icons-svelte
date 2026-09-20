<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oox-7jbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oox-7jbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:asterisk" {...props}></Icon>
