<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh6ubd6eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nh6ubd6eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:databases-fill" {...props}></Icon>
