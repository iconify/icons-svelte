<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hukoubbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hukoubbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:backrest-light" {...props}></Icon>
