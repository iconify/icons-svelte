<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hupxt07cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hupxt07cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-lucky-cat-bold" {...props}></Icon>
