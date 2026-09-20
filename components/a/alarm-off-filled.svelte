<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou5in381b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ou5in381b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alarm-off-filled" {...props}></Icon>
