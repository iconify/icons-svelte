<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt42c3erm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt42c3erm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:plus" {...props}></Icon>
