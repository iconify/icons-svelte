<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyjin6bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyjin6bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cut-24" {...props}></Icon>
