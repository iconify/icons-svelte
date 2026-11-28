<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aidyh2m1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aidyh2m1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:notebook-x" {...props}></Icon>
