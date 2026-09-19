<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9e5wubrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="e9e5wubrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:crown" {...props}></Icon>
