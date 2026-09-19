<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxonpi7xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="uxonpi7xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:contrast" {...props}></Icon>
