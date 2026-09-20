<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ulokacj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2ulokacj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rectangular-prism" {...props}></Icon>
