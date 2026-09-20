<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbfwtcrgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbfwtcrgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ppc" {...props}></Icon>
