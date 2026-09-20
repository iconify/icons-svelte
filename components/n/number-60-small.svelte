<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w47rdybzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w47rdybzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-60-small" {...props}></Icon>
