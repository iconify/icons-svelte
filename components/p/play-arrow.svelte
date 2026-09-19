<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwxdjgdbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwxdjgdbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:play-arrow" {...props}></Icon>
