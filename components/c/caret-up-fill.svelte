<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dum4ig9bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dum4ig9bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:caret-up-fill" {...props}></Icon>
