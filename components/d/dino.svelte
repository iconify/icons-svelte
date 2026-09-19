<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln2z1rd5k.css';
import '../../css/o/osq-njbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln2z1rd5k"/><path class="osq-njbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dino" {...props}></Icon>
