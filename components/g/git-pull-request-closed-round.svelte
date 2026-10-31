<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5sok3blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5sok3blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-pull-request-closed-round" {...props}></Icon>
