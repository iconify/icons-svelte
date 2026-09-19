<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq5ve83fc.css';
import '../../css/o/o4q7kwbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wq5ve83fc"/><path class="o4q7kwbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-mail" {...props}></Icon>
