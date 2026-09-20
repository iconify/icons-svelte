<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvx3k5b5o.css';
import '../../css/f/f3yq4bbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hvx3k5b5o"/><path class="f3yq4bbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:clear" {...props}></Icon>
