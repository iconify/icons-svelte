<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6gwrmjs.css';
import '../../css/d/dvrp8ybci.css';
import '../../css/w/wo-i5ub4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path clip-rule="evenodd" class="dvrp8ybci"/><path class="wo-i5ub4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-user-bold-duotone" {...props}></Icon>
