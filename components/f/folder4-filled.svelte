<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3nbb6b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3nbb6b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder4-filled" {...props}></Icon>
