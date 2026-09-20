<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqw4tx2is.css';
import '../../css/w/wgp3imbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqw4tx2is"/><path clip-rule="evenodd" class="wgp3imbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:album-fill" {...props}></Icon>
