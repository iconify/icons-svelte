<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgc7dfzhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qgc7dfzhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-confluence-20" {...props}></Icon>
