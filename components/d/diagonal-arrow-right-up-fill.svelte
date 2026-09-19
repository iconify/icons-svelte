<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfuo3_qvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfuo3_qvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:diagonal-arrow-right-up-fill" {...props}></Icon>
