<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uczo_kpja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uczo_kpja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fisker" {...props}></Icon>
