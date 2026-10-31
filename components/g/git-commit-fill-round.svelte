<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnay0bb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnay0bb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-commit-fill-round" {...props}></Icon>
