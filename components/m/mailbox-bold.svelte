<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f284zkd5g.css';
import '../../css/u/urwlvr1tl.css';
import '../../css/o/oxxeywbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f284zkd5g"/><path class="urwlvr1tl"/><path class="oxxeywbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mailbox-bold" {...props}></Icon>
