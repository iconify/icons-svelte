<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuvlcobzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuvlcobzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-lastfm" {...props}></Icon>
