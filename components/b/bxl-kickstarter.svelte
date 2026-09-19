<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4u949m8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4u949m8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-kickstarter" {...props}></Icon>
