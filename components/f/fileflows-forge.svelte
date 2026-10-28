<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiowh3tts.css';
import '../../css/m/mujo0i2yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fiowh3tts"/><path class="mujo0i2yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows-forge" {...props}></Icon>
