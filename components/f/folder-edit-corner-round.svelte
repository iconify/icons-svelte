<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_3ad4bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_3ad4bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-edit-corner-round" {...props}></Icon>
