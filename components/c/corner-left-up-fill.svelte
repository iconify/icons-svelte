<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_4187b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_4187b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:corner-left-up-fill" {...props}></Icon>
