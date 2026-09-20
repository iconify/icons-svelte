<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrd6dk6om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wrd6dk6om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:car" {...props}></Icon>
