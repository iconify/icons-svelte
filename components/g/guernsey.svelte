<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmibc4bxr.css';
import '../../css/y/yseqrvb7u.css';
import '../../css/y/y6mw4bcmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="yseqrvb7u"/><path class="y6mw4bcmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:guernsey" {...props}></Icon>
