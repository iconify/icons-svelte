<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qidz9ubar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qidz9ubar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-three-quarter" {...props}></Icon>
