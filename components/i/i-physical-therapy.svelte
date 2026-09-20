<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_j3ow9vl.css';
import '../../css/o/o0ujm8bpz.css';
import '../../css/s/s3nxbqbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="c_j3ow9vl"/><path class="o0ujm8bpz"/><path class="s3nxbqbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-physical-therapy" {...props}></Icon>
