<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwnzidx4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwnzidx4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:banknote-filled" {...props}></Icon>
