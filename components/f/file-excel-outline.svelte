<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2h4lew8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2h4lew8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-excel-outline" {...props}></Icon>
