<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdesz4bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdesz4bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-medal" {...props}></Icon>
