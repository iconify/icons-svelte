<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2k121bbm.css';
import '../../css/u/uf6yksbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2k121bbm"/><path class="uf6yksbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:refresh-ccw-alt-dot-filled" {...props}></Icon>
