<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk6a6dbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dk6a6dbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ear-with-hearing-aid" {...props}></Icon>
