<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu1bc8bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu1bc8bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:co-working-space-laptop-bold" {...props}></Icon>
