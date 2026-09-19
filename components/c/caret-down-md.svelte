<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w18z5db_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w18z5db_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:caret-down-md" {...props}></Icon>
