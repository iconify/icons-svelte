<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzh4x-bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzh4x-bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:partly-cloud-daytime-line" {...props}></Icon>
