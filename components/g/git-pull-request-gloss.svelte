<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4e9-m38q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4e9-m38q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-pull-request-gloss" {...props}></Icon>
