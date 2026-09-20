<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daiyp3bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="daiyp3bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:compass-filled" {...props}></Icon>
