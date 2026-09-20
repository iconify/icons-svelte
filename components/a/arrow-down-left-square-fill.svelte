<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7dlsnbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7dlsnbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-down-left-square-fill" {...props}></Icon>
