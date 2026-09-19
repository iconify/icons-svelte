<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqoppnb6n.css';
import '../../css/a/aps6ewwol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqoppnb6n"/><path class="aps6ewwol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brightness" {...props}></Icon>
