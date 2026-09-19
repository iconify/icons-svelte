<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns1k3pfla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns1k3pfla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:calendar-days" {...props}></Icon>
