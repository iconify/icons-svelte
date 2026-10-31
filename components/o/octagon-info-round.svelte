<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seix-klrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seix-klrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-info-round" {...props}></Icon>
