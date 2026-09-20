<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sarw6hbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sarw6hbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-enabled-fill" {...props}></Icon>
