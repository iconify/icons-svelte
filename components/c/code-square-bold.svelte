<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uinu-dbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uinu-dbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-square-bold" {...props}></Icon>
