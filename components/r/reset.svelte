<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocbloe1-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ocbloe1-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:reset" {...props}></Icon>
