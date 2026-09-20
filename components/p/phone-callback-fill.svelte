<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypft5mbdm.css';
import '../../css/j/jdgd8ngaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypft5mbdm"/><path class="jdgd8ngaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-callback-fill" {...props}></Icon>
