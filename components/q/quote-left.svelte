<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahldpgp5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="ahldpgp5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:quote-left" {...props}></Icon>
