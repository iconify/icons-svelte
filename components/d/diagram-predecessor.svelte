<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba9kzxzit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba9kzxzit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:diagram-predecessor" {...props}></Icon>
