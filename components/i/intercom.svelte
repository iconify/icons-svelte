<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p777b5bsc.css';
import '../../css/i/iic8aijvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p777b5bsc"/><path class="iic8aijvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:intercom" {...props}></Icon>
