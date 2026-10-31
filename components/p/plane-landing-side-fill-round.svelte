<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqh9pub3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqh9pub3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-landing-side-fill-round" {...props}></Icon>
