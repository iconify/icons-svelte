<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3ijz1trd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3ijz1trd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-filled" {...props}></Icon>
