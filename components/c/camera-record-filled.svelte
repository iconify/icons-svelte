<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygyfef5pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygyfef5pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera-record-filled" {...props}></Icon>
