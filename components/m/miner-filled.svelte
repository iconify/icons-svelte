<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef4civ4fj.css';
import '../../css/n/nbf3jcbto.css';
import '../../css/d/dj_zfb5pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef4civ4fj"/><path clip-rule="evenodd" class="nbf3jcbto"/><path clip-rule="evenodd" class="dj_zfb5pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:miner-filled" {...props}></Icon>
