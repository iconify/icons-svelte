<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b516c6bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b516c6bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:key-alt-minus" {...props}></Icon>
