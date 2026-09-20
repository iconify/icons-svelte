<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gugip7bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gugip7bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-3" {...props}></Icon>
