<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2l1q2ahw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2l1q2ahw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:diff" {...props}></Icon>
