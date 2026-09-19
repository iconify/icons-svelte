<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsw5pew7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="hsw5pew7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-sm-stroke-16" {...props}></Icon>
