<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw5mhy1wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw5mhy1wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-69-small" {...props}></Icon>
