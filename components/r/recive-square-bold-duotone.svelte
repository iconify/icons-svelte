<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjkn6nbgz.css';
import '../../css/b/boa7bx3yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjkn6nbgz"/><path class="boa7bx3yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:recive-square-bold-duotone" {...props}></Icon>
