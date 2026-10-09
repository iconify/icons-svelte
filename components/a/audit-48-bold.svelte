<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwgv7ib-v.css';
import '../../css/v/vk1vhpblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jwgv7ib-v"/><path class="vk1vhpblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:audit-48-bold" {...props}></Icon>
