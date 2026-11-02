<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v77_sjkpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v77_sjkpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-commit-horizontal-fill" {...props}></Icon>
