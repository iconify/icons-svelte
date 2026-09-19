<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbw-gabhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbw-gabhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-big-down-filled" {...props}></Icon>
