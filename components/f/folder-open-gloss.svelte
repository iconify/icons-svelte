<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycy3tlwgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycy3tlwgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-open-gloss" {...props}></Icon>
