<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9rwxccsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9rwxccsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cross" {...props}></Icon>
