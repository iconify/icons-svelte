<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atn4ffvgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="atn4ffvgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:alert-circle-filled" {...props}></Icon>
