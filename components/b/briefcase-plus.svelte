<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot2v1db-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot2v1db-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:briefcase-plus" {...props}></Icon>
