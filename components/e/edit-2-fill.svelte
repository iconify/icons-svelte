<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv1rtebcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv1rtebcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:edit-2-fill" {...props}></Icon>
