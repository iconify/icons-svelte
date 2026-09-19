<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqgj4jwat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqgj4jwat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-studio-2nd" {...props}></Icon>
