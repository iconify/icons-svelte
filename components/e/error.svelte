<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdi7wib5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="qdi7wib5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:error" {...props}></Icon>
