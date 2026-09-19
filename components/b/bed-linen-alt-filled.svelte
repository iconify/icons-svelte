<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm-mfbn3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nm-mfbn3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bed-linen-alt-filled" {...props}></Icon>
