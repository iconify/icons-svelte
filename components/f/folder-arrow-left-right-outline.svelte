<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x626upbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x626upbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-arrow-left-right-outline" {...props}></Icon>
