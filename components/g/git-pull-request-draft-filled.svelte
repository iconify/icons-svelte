<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv5racc8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv5racc8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-pull-request-draft-filled" {...props}></Icon>
