<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm81tbcuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm81tbcuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:cart" {...props}></Icon>
