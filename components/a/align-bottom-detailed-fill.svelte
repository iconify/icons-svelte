<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj5qrwuif.css';
import '../../css/z/z1iti509n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj5qrwuif"/><path clip-rule="evenodd" class="z1iti509n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-bottom-detailed-fill" {...props}></Icon>
