<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhqpdb.css';
import '../../css/s/so-from-38.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhqpdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:play-filled" {...props}></Icon>
