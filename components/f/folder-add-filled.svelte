<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iedg4rbcc.css';
import '../../css/k/kdpqefbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iedg4rbcc"/><path class="kdpqefbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-add-filled" {...props}></Icon>
