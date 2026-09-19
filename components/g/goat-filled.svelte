<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl4opnbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zl4opnbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:goat-filled" {...props}></Icon>
