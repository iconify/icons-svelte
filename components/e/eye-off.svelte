<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_-pb6bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_-pb6bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:eye-off" {...props}></Icon>
