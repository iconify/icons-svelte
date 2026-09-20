<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5yb73bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="b5yb73bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:renewsubscription" {...props}></Icon>
