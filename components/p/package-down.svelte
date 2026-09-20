<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf4wu4gsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf4wu4gsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:package-down" {...props}></Icon>
