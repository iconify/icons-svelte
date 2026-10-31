<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw3kgqb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw3kgqb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-edit-fill-round" {...props}></Icon>
