<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8kdzcw4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8kdzcw4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:messages" {...props}></Icon>
