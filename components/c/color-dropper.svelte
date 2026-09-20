<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6u44ac-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="d6u44ac-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:color-dropper" {...props}></Icon>
