<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuk2eibqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuk2eibqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:note" {...props}></Icon>
