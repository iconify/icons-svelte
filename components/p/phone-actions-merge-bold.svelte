<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7o0d5k6d.css';
import '../../css/p/p0-xxqbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7o0d5k6d"/><path class="p0-xxqbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:phone-actions-merge-bold" {...props}></Icon>
