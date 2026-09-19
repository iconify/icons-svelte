<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5k2r532v.css';
import '../../css/h/hm-ebxrua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5k2r532v"/><path class="hm-ebxrua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:quota" {...props}></Icon>
