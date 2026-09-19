<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kryzqjbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kryzqjbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:datacite-square" {...props}></Icon>
