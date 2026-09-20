<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs9dfd7xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fs9dfd7xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-outline" {...props}></Icon>
