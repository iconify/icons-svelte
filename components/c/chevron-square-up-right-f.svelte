<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc2b2hbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="xc2b2hbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-square-up-right-f" {...props}></Icon>
