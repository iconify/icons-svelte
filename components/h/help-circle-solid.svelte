<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc_2rzbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rc_2rzbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:help-circle-solid" {...props}></Icon>
