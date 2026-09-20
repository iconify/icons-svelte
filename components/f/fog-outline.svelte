<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3v_fcbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3v_fcbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fog-outline" {...props}></Icon>
