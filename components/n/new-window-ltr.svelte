<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrm89iuuq.css';
import '../../css/k/k7rihbbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hrm89iuuq"/><path class="k7rihbbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:new-window-ltr" {...props}></Icon>
