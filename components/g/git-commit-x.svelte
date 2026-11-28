<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a64j45bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a64j45bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:git-commit-x" {...props}></Icon>
