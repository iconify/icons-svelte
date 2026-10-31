<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulw2hdb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulw2hdb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-download-round" {...props}></Icon>
