<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsy0p32fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lsy0p32fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:restricted" {...props}></Icon>
