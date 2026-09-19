<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgd-exbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":999,"height":1000};
const content = `<path class="jgd-exbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-squint" {...props}></Icon>
