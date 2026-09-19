<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo995zbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qo995zbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:emacs" {...props}></Icon>
