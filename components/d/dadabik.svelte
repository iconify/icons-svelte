<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nejg-xwoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nejg-xwoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dadabik" {...props}></Icon>
