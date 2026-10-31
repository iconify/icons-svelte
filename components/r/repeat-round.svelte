<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obdtc0bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obdtc0bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:repeat-round" {...props}></Icon>
