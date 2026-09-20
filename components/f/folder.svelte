<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krg18ob7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krg18ob7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:folder" {...props}></Icon>
