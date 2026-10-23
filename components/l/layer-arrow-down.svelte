<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okzgdh2-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okzgdh2-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layer-arrow-down" {...props}></Icon>
