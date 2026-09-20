<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csnq9achd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csnq9achd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-10-box-multiple-outline" {...props}></Icon>
