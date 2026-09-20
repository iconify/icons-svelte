<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-x-aztdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-x-aztdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:credit-card-fill" {...props}></Icon>
