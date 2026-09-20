<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te2583bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te2583bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-off-sharp" {...props}></Icon>
