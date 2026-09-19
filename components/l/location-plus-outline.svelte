<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5rdgsbpl.css';
import '../../css/i/ipz_6dbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5rdgsbpl"/><path clip-rule="evenodd" class="ipz_6dbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:location-plus-outline" {...props}></Icon>
