<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kye07wy2c.css';
import '../../css/b/bz70mjb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kye07wy2c"/><path clip-rule="evenodd" class="bz70mjb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-favourite-bold" {...props}></Icon>
