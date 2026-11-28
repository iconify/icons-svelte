<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjyrm0bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kjyrm0bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jewel-outline" {...props}></Icon>
