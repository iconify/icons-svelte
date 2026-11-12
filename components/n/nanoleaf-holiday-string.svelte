<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3hc92b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3hc92b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-holiday-string" {...props}></Icon>
