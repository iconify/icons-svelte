<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd7vs07pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd7vs07pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:list-settings-fill" {...props}></Icon>
