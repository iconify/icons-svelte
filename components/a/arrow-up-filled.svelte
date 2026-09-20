<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpv0asbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpv0asbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-filled" {...props}></Icon>
