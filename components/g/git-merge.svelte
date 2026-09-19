<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjreeci1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kjreeci1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:git-merge" {...props}></Icon>
