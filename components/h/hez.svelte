<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwerzcbov.css';
import '../../css/n/n4xd9jpho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwerzcbov"/><path class="n4xd9jpho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hez" {...props}></Icon>
