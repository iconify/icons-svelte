<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7rhw8b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7rhw8b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rider" {...props}></Icon>
