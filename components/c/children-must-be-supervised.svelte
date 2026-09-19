<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjs2h1e2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjs2h1e2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:children-must-be-supervised" {...props}></Icon>
