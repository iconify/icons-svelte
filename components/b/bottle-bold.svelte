<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfojp41_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cfojp41_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bottle-bold" {...props}></Icon>
