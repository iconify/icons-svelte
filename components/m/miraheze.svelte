<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-49nq6dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-49nq6dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:miraheze" {...props}></Icon>
