<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgtxotrij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgtxotrij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-commit-line" {...props}></Icon>
