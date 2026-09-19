<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkf38lbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zkf38lbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:flask-solid" {...props}></Icon>
