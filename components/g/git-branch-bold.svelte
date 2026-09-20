<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp4ovabot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp4ovabot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:git-branch-bold" {...props}></Icon>
