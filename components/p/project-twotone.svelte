<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc8-4tb2b.css';
import '../../css/o/o_h68bqcq.css';
import '../../css/i/ii0xarb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="o_h68bqcq"/><path class="ii0xarb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:project-twotone" {...props}></Icon>
