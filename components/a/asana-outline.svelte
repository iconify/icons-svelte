<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zztt8vqsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zztt8vqsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:asana-outline" {...props}></Icon>
