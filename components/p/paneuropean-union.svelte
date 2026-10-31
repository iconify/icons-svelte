<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piivihhtn.css';
import '../../css/i/i28mt_bch.css';
import '../../css/c/cwdx-acsy.css';
import '../../css/g/greuegb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="piivihhtn"/><path class="i28mt_bch"/><path class="cwdx-acsy"/><path class="greuegb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:paneuropean-union" {...props}></Icon>
