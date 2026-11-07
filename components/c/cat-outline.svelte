<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnluy6pil.css';
import '../../css/b/bgpfsd5wd.css';
import '../../css/b/bmq6w9aab.css';
import '../../css/l/lmovn-nth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wnluy6pil"/><path class="bgpfsd5wd"/><path class="bmq6w9aab"/><path clip-rule="evenodd" class="lmovn-nth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cat-outline" {...props}></Icon>
