<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmbv34e3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmbv34e3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flag-fill" {...props}></Icon>
