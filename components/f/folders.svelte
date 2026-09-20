<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo_nnibyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo_nnibyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folders" {...props}></Icon>
