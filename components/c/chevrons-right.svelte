<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eref7llez.css';
import '../../css/b/bxv5csb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eref7llez"/><path class="bxv5csb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevrons-right" {...props}></Icon>
