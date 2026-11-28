<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6m7u3bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6m7u3bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:motorbike" {...props}></Icon>
