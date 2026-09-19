<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkgu3wbhs.css';
import '../../css/d/ds9yhnr-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkgu3wbhs"/><path class="ds9yhnr-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chat-alt" {...props}></Icon>
