<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l503qdb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l503qdb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-outline" {...props}></Icon>
