<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slwo16b5l.css';
import '../../css/u/uv22sacky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slwo16b5l"/><path class="uv22sacky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ear-alt" {...props}></Icon>
