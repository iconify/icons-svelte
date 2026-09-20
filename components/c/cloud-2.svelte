<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa46xtaxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa46xtaxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-2" {...props}></Icon>
