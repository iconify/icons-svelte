<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqq00trif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqq00trif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:equal" {...props}></Icon>
