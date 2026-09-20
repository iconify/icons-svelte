<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q26vg3huj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q26vg3huj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:check-double" {...props}></Icon>
