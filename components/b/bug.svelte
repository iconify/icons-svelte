<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e618xc-zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="e618xc-zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:bug" {...props}></Icon>
