<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbo7c_jnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbo7c_jnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:medal-square" {...props}></Icon>
