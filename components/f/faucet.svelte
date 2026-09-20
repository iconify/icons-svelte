<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwti5uqfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cwti5uqfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:faucet" {...props}></Icon>
