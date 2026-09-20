<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrpo78owk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrpo78owk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:karate" {...props}></Icon>
