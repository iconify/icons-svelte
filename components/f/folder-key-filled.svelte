<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw4bdbblf.css';
import '../../css/i/i2s-32vgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw4bdbblf"/><path class="i2s-32vgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-key-filled" {...props}></Icon>
