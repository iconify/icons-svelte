<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4w-4_rrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4w-4_rrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:drag-vertical-fill" {...props}></Icon>
