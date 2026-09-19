<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ol2bc_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ol2bc_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:link-break" {...props}></Icon>
