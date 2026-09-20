<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omhq2obvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omhq2obvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:document-code-filled" {...props}></Icon>
