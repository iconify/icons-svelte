<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdsnftr8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdsnftr8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments" {...props}></Icon>
