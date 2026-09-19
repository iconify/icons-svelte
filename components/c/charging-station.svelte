<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4inzjyce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="v4inzjyce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:charging-station" {...props}></Icon>
