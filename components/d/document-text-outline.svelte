<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2m2g7b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a2m2g7b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-text-outline" {...props}></Icon>
