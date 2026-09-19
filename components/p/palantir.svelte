<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tikpp7byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tikpp7byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:palantir" {...props}></Icon>
