<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1-aahsdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1-aahsdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:down-right-2-short-arrow" {...props}></Icon>
