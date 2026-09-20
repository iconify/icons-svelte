<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu0-_oxqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wu0-_oxqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-attachment-1-attachment-link-paperclip-unlink" {...props}></Icon>
