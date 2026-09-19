<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgwi26b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgwi26b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:options-outline" {...props}></Icon>
