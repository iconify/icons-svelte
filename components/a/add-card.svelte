<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_d2dzlwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="n_d2dzlwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:add-card" {...props}></Icon>
