<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a20z3n5cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a20z3n5cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-4-fill" {...props}></Icon>
