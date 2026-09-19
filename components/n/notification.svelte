<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byk0tmp-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="byk0tmp-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:notification" {...props}></Icon>
