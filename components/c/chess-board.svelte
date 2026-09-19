<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm4e25hpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nm4e25hpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chess-board" {...props}></Icon>
