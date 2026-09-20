<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lky9-3e9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lky9-3e9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:noun-project" {...props}></Icon>
