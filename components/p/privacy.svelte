<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgack7b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="jgack7b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:privacy" {...props}></Icon>
