<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9687bcgq.css';
import '../../css/p/po09tr52l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9687bcgq"/><path clip-rule="evenodd" class="po09tr52l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pencil-single" {...props}></Icon>
