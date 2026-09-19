<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulfpgv-qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulfpgv-qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:invader" {...props}></Icon>
