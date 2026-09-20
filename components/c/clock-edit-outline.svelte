<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi6oorb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi6oorb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-edit-outline" {...props}></Icon>
