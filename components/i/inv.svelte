<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noh1fb71d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="noh1fb71d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:inv" {...props}></Icon>
