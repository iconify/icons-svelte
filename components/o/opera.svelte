<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f33f75blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":851,"height":1000};
const content = `<path class="f33f75blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:opera" {...props}></Icon>
