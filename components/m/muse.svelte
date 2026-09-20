<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cscw25bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cscw25bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:muse" {...props}></Icon>
