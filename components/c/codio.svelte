<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoihrz1aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoihrz1aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codio" {...props}></Icon>
