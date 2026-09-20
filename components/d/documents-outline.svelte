<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpaxtlxsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpaxtlxsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:documents-outline" {...props}></Icon>
