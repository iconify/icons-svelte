<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmwvu5eco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmwvu5eco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chevron-start-double" {...props}></Icon>
