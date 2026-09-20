<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2fdeh9wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2fdeh9wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:align-text-center-remix" {...props}></Icon>
