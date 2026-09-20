<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7zv08aim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7zv08aim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:delete-empty-outline" {...props}></Icon>
