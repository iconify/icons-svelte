<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezyzqbcsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezyzqbcsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-distribute-left" {...props}></Icon>
