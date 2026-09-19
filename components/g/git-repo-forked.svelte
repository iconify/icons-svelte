<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e99tndktk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e99tndktk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:git-repo-forked" {...props}></Icon>
