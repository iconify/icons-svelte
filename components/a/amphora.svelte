<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j71kse4ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j71kse4ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:amphora" {...props}></Icon>
