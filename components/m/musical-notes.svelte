<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lytt0db4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="lytt0db4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:musical-notes" {...props}></Icon>
