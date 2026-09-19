<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1pworb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1pworb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-fill" {...props}></Icon>
