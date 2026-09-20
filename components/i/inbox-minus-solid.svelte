<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqaxb0b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqaxb0b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:inbox-minus-solid" {...props}></Icon>
