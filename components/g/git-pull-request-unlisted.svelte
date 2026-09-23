<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kps4-xb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kps4-xb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:git-pull-request-unlisted" {...props}></Icon>
