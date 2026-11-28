<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vujq3pbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vujq3pbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bathtub-solid" {...props}></Icon>
