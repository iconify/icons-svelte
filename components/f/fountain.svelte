<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh08eyq3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jh08eyq3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fountain" {...props}></Icon>
