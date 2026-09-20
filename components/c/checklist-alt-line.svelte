<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd6rmkbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd6rmkbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:checklist-alt-line" {...props}></Icon>
