<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx1fzq_8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx1fzq_8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:lastfm" {...props}></Icon>
