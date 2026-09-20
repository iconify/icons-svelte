<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so43afb2h.css';
import '../../css/u/u399owb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so43afb2h"/><path clip-rule="evenodd" class="u399owb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cam-video-duotone" {...props}></Icon>
