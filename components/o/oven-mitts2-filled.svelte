<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqp1_dbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqp1_dbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:oven-mitts2-filled" {...props}></Icon>
