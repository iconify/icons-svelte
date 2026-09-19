<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0v8bqb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0v8bqb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:path-back" {...props}></Icon>
