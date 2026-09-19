<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnzkw5bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnzkw5bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:homemati-ip" {...props}></Icon>
