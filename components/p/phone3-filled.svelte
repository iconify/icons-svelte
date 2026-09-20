<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3zaxj93e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3zaxj93e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone3-filled" {...props}></Icon>
