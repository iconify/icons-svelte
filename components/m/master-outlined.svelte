<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6knii7dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6knii7dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:master-outlined" {...props}></Icon>
