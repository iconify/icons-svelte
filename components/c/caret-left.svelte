<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuely1bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuely1bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:caret-left" {...props}></Icon>
