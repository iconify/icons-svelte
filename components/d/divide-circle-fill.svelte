<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxo2_4bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uxo2_4bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:divide-circle-fill" {...props}></Icon>
