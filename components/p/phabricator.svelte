<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7-1w7biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o7-1w7biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:phabricator" {...props}></Icon>
