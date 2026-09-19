<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvrzt5bkz.css';
import '../../css/m/mv8a-mbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvrzt5bkz"/><path class="mv8a-mbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microphone-big" {...props}></Icon>
