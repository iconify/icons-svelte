<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihldf-44r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihldf-44r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:monitor" {...props}></Icon>
