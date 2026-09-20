<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q21sykgee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q21sykgee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-code" {...props}></Icon>
