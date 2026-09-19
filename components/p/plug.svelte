<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x36pa5t6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x36pa5t6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:plug" {...props}></Icon>
