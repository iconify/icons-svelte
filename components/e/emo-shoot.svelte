<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo56wubgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1948,"height":1000};
const content = `<path class="lo56wubgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-shoot" {...props}></Icon>
