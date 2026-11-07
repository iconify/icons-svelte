<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_6cwfbbm.css';
import '../../css/z/zoahz159d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_6cwfbbm"/><path clip-rule="evenodd" class="zoahz159d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-open-outline" {...props}></Icon>
