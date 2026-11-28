<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp_2rq63l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp_2rq63l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-left-square-solid" {...props}></Icon>
