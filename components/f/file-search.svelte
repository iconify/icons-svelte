<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sia2ghlsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sia2ghlsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-search" {...props}></Icon>
