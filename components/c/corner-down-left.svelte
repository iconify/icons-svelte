<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyfjpwsme.css';
import '../../css/d/d_33tyskh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyfjpwsme wm-k"/><path class="d_33tyskh wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:corner-down-left" {...props}></Icon>
