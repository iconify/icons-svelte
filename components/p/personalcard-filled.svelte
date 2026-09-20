<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-jc7bb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-jc7bb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:personalcard-filled" {...props}></Icon>
