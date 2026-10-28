<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lavxv1b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lavxv1b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:git-pull-request-closed-ai" {...props}></Icon>
