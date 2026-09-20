<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcsflbivf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcsflbivf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:osano" {...props}></Icon>
