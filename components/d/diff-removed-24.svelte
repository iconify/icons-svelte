<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6_y8wh0z.css';
import '../../css/c/c485hsbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6_y8wh0z"/><path class="c485hsbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-removed-24" {...props}></Icon>
