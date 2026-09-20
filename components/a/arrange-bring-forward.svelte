<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpzk0ubvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpzk0ubvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrange-bring-forward" {...props}></Icon>
