<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i58hs0j8m.css';
import '../../css/l/l-lriixbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i58hs0j8m"/><path clip-rule="evenodd" class="l-lriixbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-music-2-bold" {...props}></Icon>
