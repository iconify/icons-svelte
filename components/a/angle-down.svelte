<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9xyacbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9xyacbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:angle-down" {...props}></Icon>
