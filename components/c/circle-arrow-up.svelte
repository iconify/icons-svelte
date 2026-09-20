<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf-3i8bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tf-3i8bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-up" {...props}></Icon>
