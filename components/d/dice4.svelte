<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udwsy0bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="udwsy0bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dice4" {...props}></Icon>
