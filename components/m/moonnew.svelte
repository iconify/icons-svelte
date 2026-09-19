<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh_576bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jh_576bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:moonnew" {...props}></Icon>
