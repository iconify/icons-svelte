<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcpe4647d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcpe4647d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:btcst" {...props}></Icon>
