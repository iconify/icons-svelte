<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c17h2ub6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c17h2ub6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:chevron-left-small" {...props}></Icon>
