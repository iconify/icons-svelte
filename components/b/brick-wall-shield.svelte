<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aij7kmbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aij7kmbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:brick-wall-shield" {...props}></Icon>
