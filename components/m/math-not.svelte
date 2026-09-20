<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzv92pz5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzv92pz5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-not" {...props}></Icon>
