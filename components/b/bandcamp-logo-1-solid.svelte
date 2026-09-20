<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj_l_4b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nj_l_4b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bandcamp-logo-1-solid" {...props}></Icon>
