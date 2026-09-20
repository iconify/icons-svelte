<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqn-dor0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqn-dor0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grammerly-filled" {...props}></Icon>
