<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdr_c_a_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdr_c_a_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clear-day-fill" {...props}></Icon>
