<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evsd6q7sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evsd6q7sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googledatastudio" {...props}></Icon>
