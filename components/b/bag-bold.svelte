<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c74uzd3ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c74uzd3ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-bold" {...props}></Icon>
