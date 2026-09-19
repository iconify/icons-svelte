<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk55etb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uk55etb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pinescript" {...props}></Icon>
