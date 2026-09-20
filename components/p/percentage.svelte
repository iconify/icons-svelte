<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjp61tb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjp61tb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:percentage" {...props}></Icon>
