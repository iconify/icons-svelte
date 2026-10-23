<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opbdrbc-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opbdrbc-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:georgian-lari" {...props}></Icon>
