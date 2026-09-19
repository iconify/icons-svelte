<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vru8ler2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="vru8ler2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-swimming" {...props}></Icon>
