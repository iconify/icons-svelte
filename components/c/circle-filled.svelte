<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcz4m5c4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<circle class="kcz4m5c4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:circle-filled" {...props}></Icon>
