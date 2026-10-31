<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1uee2bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1uee2bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-pull-request-draft-round" {...props}></Icon>
