<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3utn-y9c.css';
import '../../css/w/waww24_9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3utn-y9c"/><path class="waww24_9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bug-alt" {...props}></Icon>
