<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3_mw7w9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3_mw7w9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:educative" {...props}></Icon>
