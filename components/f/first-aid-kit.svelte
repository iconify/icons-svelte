<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1n15habz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1n15habz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:first-aid-kit" {...props}></Icon>
