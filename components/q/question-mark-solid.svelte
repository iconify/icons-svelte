<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwio0wbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zwio0wbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:question-mark-solid" {...props}></Icon>
