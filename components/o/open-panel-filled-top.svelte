<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wob2l3rnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wob2l3rnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:open-panel-filled-top" {...props}></Icon>
