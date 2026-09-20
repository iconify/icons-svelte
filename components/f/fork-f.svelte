<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_xli40hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="w_xli40hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:fork-f" {...props}></Icon>
