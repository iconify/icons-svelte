<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pckrh5b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pckrh5b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:crop" {...props}></Icon>
