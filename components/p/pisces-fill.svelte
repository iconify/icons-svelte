<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-lld0-aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-lld0-aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pisces-fill" {...props}></Icon>
