<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unnhiupqa.css';
import '../../css/o/o64ssnoeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="unnhiupqa"/><path class="o64ssnoeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pivot-column-16" {...props}></Icon>
