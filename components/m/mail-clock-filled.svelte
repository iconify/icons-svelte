<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo3fevbda.css';
import '../../css/i/i-_k0ewmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wo3fevbda"/><path class="i-_k0ewmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-clock-filled" {...props}></Icon>
