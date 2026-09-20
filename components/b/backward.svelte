<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-7rrlbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-7rrlbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:backward" {...props}></Icon>
