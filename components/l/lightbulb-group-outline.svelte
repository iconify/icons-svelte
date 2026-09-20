<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t44l9wbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t44l9wbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-group-outline" {...props}></Icon>
