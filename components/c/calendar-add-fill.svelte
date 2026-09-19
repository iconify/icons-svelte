<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mal-cabtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mal-cabtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-add-fill" {...props}></Icon>
