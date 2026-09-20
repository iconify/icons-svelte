<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3dc3r9sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z3dc3r9sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hq-filled" {...props}></Icon>
