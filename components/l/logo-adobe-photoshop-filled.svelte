<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6qf9oyxh.css';
import '../../css/i/i-nkzdl-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6qf9oyxh"/><path class="i-nkzdl-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-adobe-photoshop-filled" {...props}></Icon>
