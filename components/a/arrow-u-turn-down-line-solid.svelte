<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_a-9r90o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_a-9r90o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-down-line-solid" {...props}></Icon>
