<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdab8wejo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="cdab8wejo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:check-book" {...props}></Icon>
