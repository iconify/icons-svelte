<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkghzybvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkghzybvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:list" {...props}></Icon>
