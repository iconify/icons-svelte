<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-sr4acye.css';
import '../../css/s/slj16rbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-sr4acye"/><path clip-rule="evenodd" class="slj16rbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:hdd-24" {...props}></Icon>
