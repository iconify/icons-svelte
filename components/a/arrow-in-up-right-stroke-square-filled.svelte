<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2k6oubdw.css';
import '../../css/k/kwq8pvbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2k6oubdw"/><path class="kwq8pvbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-right-stroke-square-filled" {...props}></Icon>
