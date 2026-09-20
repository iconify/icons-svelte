<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgv9xlbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgv9xlbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cycling" {...props}></Icon>
