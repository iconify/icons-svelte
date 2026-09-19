<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u20c2ybqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u20c2ybqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:grid-plus-filled" {...props}></Icon>
