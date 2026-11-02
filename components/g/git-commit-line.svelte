<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt7zskbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt7zskbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-commit-line" {...props}></Icon>
