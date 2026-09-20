<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn4zp1bkf.css';
import '../../css/a/anndn7kya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn4zp1bkf"/><path class="anndn7kya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:qr-code-fill" {...props}></Icon>
