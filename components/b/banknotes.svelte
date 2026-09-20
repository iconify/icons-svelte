<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc7y2bxnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="wc7y2bxnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:banknotes" {...props}></Icon>
