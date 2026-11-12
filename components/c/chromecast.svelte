<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkk14r0wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkk14r0wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:chromecast" {...props}></Icon>
