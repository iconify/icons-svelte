<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8hhc1bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8hhc1bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:podcast-pause" {...props}></Icon>
