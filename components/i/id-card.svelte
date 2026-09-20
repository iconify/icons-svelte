<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kutx4ubdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="kutx4ubdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:id-card" {...props}></Icon>
