<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3124ccsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="a3124ccsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:play" {...props}></Icon>
