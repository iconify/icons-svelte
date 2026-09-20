<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9g1ks5wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9g1ks5wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-marker" {...props}></Icon>
