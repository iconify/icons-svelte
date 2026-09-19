<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-ol5-bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ol5-bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-branch-filled" {...props}></Icon>
