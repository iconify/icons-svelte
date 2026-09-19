<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w84vznkgo.css';
import '../../css/z/zah5plefr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w84vznkgo"/><path class="zah5plefr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ban-outline" {...props}></Icon>
