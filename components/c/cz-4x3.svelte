<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/damb695lr.css';
import '../../css/k/kavt8psvh.css';
import '../../css/x/xztbdibpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="damb695lr"/><path class="kavt8psvh"/><path class="xztbdibpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:cz-4x3" {...props}></Icon>
