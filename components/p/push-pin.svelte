<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsift9fqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jsift9fqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:push-pin" {...props}></Icon>
