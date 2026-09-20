<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi4jnnbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gi4jnnbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:color-filter-fill" {...props}></Icon>
