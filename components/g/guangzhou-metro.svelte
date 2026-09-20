<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjmha8p-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjmha8p-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:guangzhou-metro" {...props}></Icon>
