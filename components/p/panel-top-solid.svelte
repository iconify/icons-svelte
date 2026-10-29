<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rimslic0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rimslic0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-top-solid" {...props}></Icon>
