<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_j778rnr.css';
import '../../css/h/huj_k0bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n_j778rnr"/><path clip-rule="evenodd" class="huj_k0bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-talk-dark" {...props}></Icon>
