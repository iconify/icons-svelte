<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jarezk6na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jarezk6na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:end-call-rounded-broken" {...props}></Icon>
