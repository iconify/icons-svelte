<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrbkw7bqm.css';
import '../../css/o/oq2mp8bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrbkw7bqm"/><path class="oq2mp8bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:notion" {...props}></Icon>
