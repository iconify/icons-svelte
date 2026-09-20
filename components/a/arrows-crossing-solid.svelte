<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7u8auytk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7u8auytk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrows-crossing-solid" {...props}></Icon>
