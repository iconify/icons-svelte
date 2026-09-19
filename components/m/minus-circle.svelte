<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5e9wba0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5e9wba0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:minus-circle" {...props}></Icon>
