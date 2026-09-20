<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykpl97bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-3};
const content = `<path class="ykpl97bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:play" {...props}></Icon>
