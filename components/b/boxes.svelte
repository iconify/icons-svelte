<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jldvw0byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jldvw0byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:boxes" {...props}></Icon>
