<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da99er92l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="da99er92l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:repeat" {...props}></Icon>
