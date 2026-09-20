<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt5df8j4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt5df8j4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:astro" {...props}></Icon>
