<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md1sf7lxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="md1sf7lxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:open-book" {...props}></Icon>
