<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7p923thj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z7p923thj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:question-circle-outline" {...props}></Icon>
