<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtrl803vx.css';
import '../../css/e/e0-stmb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtrl803vx"/><path clip-rule="evenodd" class="e0-stmb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:banknote-arrow-up-filled" {...props}></Icon>
