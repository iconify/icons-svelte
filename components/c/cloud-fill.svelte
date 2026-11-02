<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unyy2gbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unyy2gbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-fill" {...props}></Icon>
