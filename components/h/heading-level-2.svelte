<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp2f6lb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="tp2f6lb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:heading-level-2" {...props}></Icon>
