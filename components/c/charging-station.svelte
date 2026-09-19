<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z68460bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z68460bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:charging-station" {...props}></Icon>
