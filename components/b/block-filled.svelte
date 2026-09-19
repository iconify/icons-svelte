<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd6q1996p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vd6q1996p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:block-filled" {...props}></Icon>
