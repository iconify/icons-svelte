<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqs0g3bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqs0g3bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrange-square-filled" {...props}></Icon>
