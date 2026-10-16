<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8m_o6v-h.css';
import '../../css/a/arhsv8bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s8m_o6v-h"/><path class="arhsv8bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bungalow-20-bold" {...props}></Icon>
