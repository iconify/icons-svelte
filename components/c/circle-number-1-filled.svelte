<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvmejdxts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvmejdxts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-number-1-filled" {...props}></Icon>
