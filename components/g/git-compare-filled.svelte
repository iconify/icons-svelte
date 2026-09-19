<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as0sge_bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as0sge_bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-compare-filled" {...props}></Icon>
