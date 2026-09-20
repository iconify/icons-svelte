<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4nvolk3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="v4nvolk3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:calltransfer" {...props}></Icon>
