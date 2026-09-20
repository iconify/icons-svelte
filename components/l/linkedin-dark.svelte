<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx3aksgyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx3aksgyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkedin-dark" {...props}></Icon>
