<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gttxmhbqp.css';
import '../../css/p/pa47kd49e.css';
import '../../css/s/skxbewbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gttxmhbqp"/><path class="pa47kd49e"/><path clip-rule="evenodd" class="skxbewbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-music-bold" {...props}></Icon>
