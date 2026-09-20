<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktt_d9eln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ktt_d9eln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:charging" {...props}></Icon>
