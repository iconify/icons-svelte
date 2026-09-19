<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph994hqiv.css';
import '../../css/f/fcg7ob6nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph994hqiv"/><path class="fcg7ob6nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:apartment" {...props}></Icon>
