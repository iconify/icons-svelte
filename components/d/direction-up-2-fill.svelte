<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbml36fwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbml36fwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:direction-up-2-fill" {...props}></Icon>
