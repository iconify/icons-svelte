<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2y-q-42q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2y-q-42q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:car-electric" {...props}></Icon>
