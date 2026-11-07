<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j08vyhzaj.css';
import '../../css/l/l531-vi_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j08vyhzaj"/><path class="l531-vi_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-download-outline" {...props}></Icon>
