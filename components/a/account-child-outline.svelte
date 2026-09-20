<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjksq2bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjksq2bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-child-outline" {...props}></Icon>
