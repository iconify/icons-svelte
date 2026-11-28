<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zww523woh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zww523woh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-alert" {...props}></Icon>
