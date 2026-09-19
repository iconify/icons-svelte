<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwxxpw3nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwxxpw3nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beer-alt-filled" {...props}></Icon>
