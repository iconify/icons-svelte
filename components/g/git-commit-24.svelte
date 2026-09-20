<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_d2xhq5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_d2xhq5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-commit-24" {...props}></Icon>
