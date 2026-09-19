<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0cdwoxlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0cdwoxlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:git-commit" {...props}></Icon>
