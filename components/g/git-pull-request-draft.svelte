<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj70oih2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj70oih2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-pull-request-draft" {...props}></Icon>
