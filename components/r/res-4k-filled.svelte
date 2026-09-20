<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqil5bbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oqil5bbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:res-4k-filled" {...props}></Icon>
