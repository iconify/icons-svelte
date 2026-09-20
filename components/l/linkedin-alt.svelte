<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ski76bcvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ski76bcvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:linkedin-alt" {...props}></Icon>
