<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2wholb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w2wholb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:quasar" {...props}></Icon>
