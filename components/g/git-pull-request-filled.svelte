<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh_3csxda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh_3csxda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-pull-request-filled" {...props}></Icon>
