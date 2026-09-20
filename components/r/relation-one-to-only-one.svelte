<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u12zo6b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u12zo6b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-one-to-only-one" {...props}></Icon>
