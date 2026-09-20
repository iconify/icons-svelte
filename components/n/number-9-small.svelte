<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfj4sf55g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfj4sf55g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-9-small" {...props}></Icon>
