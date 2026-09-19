<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9x_09j0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9x_09j0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:down-left-arrow" {...props}></Icon>
