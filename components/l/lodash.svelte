<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfjg4ccyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wfjg4ccyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:lodash" {...props}></Icon>
