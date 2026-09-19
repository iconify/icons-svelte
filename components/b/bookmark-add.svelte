<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbiw0ob-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbiw0ob-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bookmark-add" {...props}></Icon>
