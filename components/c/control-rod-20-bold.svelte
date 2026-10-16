<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-9c7jf-e.css';
import '../../css/l/la3uc6bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-9c7jf-e"/><path class="la3uc6bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-rod-20-bold" {...props}></Icon>
