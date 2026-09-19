<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9h80gb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9h80gb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:face-neutral-filled" {...props}></Icon>
