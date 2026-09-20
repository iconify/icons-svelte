<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg13q4bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg13q4bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:delta" {...props}></Icon>
