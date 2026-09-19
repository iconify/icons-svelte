<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4so8zrzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4so8zrzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:fire-outline" {...props}></Icon>
