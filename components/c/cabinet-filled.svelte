<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql_70zbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql_70zbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cabinet-filled" {...props}></Icon>
