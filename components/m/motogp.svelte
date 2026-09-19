<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahq7b9twm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahq7b9twm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:motogp" {...props}></Icon>
