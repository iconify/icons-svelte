<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6fl9mbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6fl9mbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-dashed-fill" {...props}></Icon>
