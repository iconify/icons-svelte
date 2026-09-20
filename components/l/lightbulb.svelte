<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9dm_5b8b.css';
import '../../css/x/x6d1mvvmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j9dm_5b8b"/><path class="x6d1mvvmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:lightbulb" {...props}></Icon>
