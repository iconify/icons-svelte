<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2-390bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2-390bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:concourse-ci" {...props}></Icon>
