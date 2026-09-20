<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu9tx1bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wu9tx1bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:file-add-alternate-remix" {...props}></Icon>
