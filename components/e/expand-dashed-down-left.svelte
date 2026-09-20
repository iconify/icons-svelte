<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7x96gbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7x96gbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-left" {...props}></Icon>
