<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcwnfy39o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcwnfy39o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-break-round" {...props}></Icon>
