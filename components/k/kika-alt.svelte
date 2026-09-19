<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brju6tbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brju6tbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:kika-alt" {...props}></Icon>
