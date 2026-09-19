<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2deosl3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2deosl3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-repo-forked" {...props}></Icon>
