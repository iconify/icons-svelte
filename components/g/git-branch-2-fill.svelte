<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbplw8bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbplw8bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-2-fill" {...props}></Icon>
