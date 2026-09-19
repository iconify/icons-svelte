<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z67eqnb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z67eqnb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-circle-left-fill" {...props}></Icon>
