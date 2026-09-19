<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfy2lccxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfy2lccxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:christianity-filled" {...props}></Icon>
