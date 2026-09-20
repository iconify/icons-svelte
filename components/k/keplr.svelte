<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2p0yrbfm.css';
import '../../css/c/cgy263brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2p0yrbfm"/><path clip-rule="evenodd" class="cgy263brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:keplr" {...props}></Icon>
