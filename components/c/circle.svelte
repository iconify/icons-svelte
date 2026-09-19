<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj51rsh9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="zj51rsh9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle" {...props}></Icon>
