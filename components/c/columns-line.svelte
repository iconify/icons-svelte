<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puieb1_ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puieb1_ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:columns-line" {...props}></Icon>
