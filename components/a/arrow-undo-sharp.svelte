<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujp3zn38v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ujp3zn38v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-undo-sharp" {...props}></Icon>
