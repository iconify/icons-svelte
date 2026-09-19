<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf0alrb_x.css';
import '../../css/c/ckevorb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bf0alrb_x"/><path class="ckevorb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:lightbulb" {...props}></Icon>
