<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ev7wbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w5ev7wbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:quotation-mark-20-solid" {...props}></Icon>
