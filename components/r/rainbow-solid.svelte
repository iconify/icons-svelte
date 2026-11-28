<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-jcrobbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-jcrobbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rainbow-solid" {...props}></Icon>
