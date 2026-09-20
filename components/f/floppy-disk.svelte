<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mavre2s5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mavre2s5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:floppy-disk" {...props}></Icon>
