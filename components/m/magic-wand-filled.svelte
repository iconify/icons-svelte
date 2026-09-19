<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cowqw2bkl.css';
import '../../css/k/knoj0abei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cowqw2bkl"/><path class="knoj0abei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:magic-wand-filled" {...props}></Icon>
