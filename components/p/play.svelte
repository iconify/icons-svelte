<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsgs6gbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsgs6gbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:play" {...props}></Icon>
