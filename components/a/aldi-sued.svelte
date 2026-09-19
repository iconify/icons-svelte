<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6v0-ubfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6v0-ubfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aldi-sued" {...props}></Icon>
