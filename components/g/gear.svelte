<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebrv74bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebrv74bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gear" {...props}></Icon>
