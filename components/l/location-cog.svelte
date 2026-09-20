<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpkia7k9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpkia7k9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-cog" {...props}></Icon>
