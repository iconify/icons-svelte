<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1v98_1ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1v98_1ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-disabled-02" {...props}></Icon>
