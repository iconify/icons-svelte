<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yes8172wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yes8172wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:done-round" {...props}></Icon>
