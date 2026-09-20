<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7e_rub6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="e7e_rub6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:check" {...props}></Icon>
