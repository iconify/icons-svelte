<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8hbf0lfj.css';
import '../../css/b/bw5sq60eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8hbf0lfj"/><path class="bw5sq60eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:inbox-filled" {...props}></Icon>
