<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu6mqqb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":696,"height":1000};
const content = `<path class="vu6mqqb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-surprised" {...props}></Icon>
