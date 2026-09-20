<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jerpqq0qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jerpqq0qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:champagne-fill" {...props}></Icon>
