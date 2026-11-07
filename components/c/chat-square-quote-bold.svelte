<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1two7b3n.css';
import '../../css/c/cwkqqicwy.css';
import '../../css/r/rgklaf5rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1two7b3n"/><path class="cwkqqicwy"/><path clip-rule="evenodd" class="rgklaf5rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-quote-bold" {...props}></Icon>
