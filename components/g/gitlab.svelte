<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paejd-bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="paejd-bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:gitlab" {...props}></Icon>
