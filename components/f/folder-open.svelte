<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br3drl69p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br3drl69p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-open" {...props}></Icon>
