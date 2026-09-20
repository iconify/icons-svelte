<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihr8-aczz.css';
import '../../css/c/cn3hh0bhi.css';
import '../../css/b/b36x5kbtc.css';
import '../../css/f/fjvtlht_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihr8-aczz"/><path class="cn3hh0bhi"/><path clip-rule="evenodd" class="b36x5kbtc"/><path clip-rule="evenodd" class="fjvtlht_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:emoji-wink-light" {...props}></Icon>
