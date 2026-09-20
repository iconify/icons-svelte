<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hji5n7yfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hji5n7yfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-sort-alt-1-line" {...props}></Icon>
