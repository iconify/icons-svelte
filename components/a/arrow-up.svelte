<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_mrlqbtl.css';
import '../../css/o/om6kf4uvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_mrlqbtl"/><path class="om6kf4uvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-up" {...props}></Icon>
