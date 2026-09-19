<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqy8bbbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqy8bbbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:close-big" {...props}></Icon>
