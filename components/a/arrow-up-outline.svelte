<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldmnugbgt.css';
import '../../css/a/aqgm4tbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldmnugbgt"/><path clip-rule="evenodd" class="aqgm4tbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:arrow-up-outline" {...props}></Icon>
