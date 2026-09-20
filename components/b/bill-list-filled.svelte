<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn1i5feok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xn1i5feok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bill-list-filled" {...props}></Icon>
