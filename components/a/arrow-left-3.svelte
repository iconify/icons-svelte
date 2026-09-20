<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a316u6-zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a316u6-zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left-3" {...props}></Icon>
