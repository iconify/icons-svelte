<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7e6b-das.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7e6b-das"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-landing-round" {...props}></Icon>
