<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo4gjv_kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo4gjv_kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pill-x" {...props}></Icon>
