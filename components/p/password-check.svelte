<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lehxzdbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lehxzdbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:password-check" {...props}></Icon>
