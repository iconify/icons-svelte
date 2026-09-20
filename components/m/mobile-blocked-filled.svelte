<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1aa_bxoc.css';
import '../../css/v/vibuei4ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1aa_bxoc"/><path class="vibuei4ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mobile-blocked-filled" {...props}></Icon>
