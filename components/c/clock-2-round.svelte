<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l273n2buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l273n2buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-2-round" {...props}></Icon>
