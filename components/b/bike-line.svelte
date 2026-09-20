<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdx0f4b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdx0f4b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bike-line" {...props}></Icon>
