<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqjyuob2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uqjyuob2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:debian" {...props}></Icon>
