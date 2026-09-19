<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayml4ibqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayml4ibqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-golfball-e14" {...props}></Icon>
