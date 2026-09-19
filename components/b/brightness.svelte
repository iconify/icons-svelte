<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1afvzb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="j1afvzb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:brightness" {...props}></Icon>
