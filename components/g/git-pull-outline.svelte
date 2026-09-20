<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3fmq6b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e3fmq6b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-pull-outline" {...props}></Icon>
