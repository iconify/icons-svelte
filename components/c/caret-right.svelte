<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr_827brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wr_827brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:caret-right" {...props}></Icon>
