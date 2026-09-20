<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyya42sbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hyya42sbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:facebook-square" {...props}></Icon>
