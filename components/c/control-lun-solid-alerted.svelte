<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu410db3i.css';
import '../../css/v/vod9qb7fk.css';
import '../../css/u/uaycyrbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="mu410db3i"/><path class="vod9qb7fk"/><path class="uaycyrbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:control-lun-solid-alerted" {...props}></Icon>
