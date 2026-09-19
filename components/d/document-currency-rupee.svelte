<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7oldikrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7oldikrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-rupee" {...props}></Icon>
