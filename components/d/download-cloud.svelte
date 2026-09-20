<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugoo86n2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugoo86n2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:download-cloud" {...props}></Icon>
