<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khtafzbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="khtafzbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:map-filled" {...props}></Icon>
