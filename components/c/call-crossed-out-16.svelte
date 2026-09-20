<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ura_37b8i.css';
import '../../css/y/y71wou8xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ura_37b8i"/><path class="y71wou8xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-crossed-out-16" {...props}></Icon>
