<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd4q3bckj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd4q3bckj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lospec" {...props}></Icon>
