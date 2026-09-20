<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7ohubbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g7ohubbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-plus-fill" {...props}></Icon>
