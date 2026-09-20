<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2wv40b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2wv40b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bcdt" {...props}></Icon>
