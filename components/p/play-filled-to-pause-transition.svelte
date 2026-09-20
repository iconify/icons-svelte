<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozyzan.css';
import '../../css/d/d-zrqjti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozyzan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:play-filled-to-pause-transition" {...props}></Icon>
