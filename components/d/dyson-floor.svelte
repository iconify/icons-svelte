<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzqlw3bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzqlw3bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dyson-floor" {...props}></Icon>
