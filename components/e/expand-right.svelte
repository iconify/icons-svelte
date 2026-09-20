<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqhovib8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="aqhovib8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:expand-right" {...props}></Icon>
