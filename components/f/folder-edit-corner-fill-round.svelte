<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-xqgtvwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-xqgtvwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-edit-corner-fill-round" {...props}></Icon>
