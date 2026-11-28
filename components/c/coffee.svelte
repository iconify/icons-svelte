<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8c5h_bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8c5h_bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:coffee" {...props}></Icon>
