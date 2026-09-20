<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss96c8byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ss96c8byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:full-trash" {...props}></Icon>
