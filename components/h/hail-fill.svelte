<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njl66hb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njl66hb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hail-fill" {...props}></Icon>
