<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqv73sbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqv73sbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:paragraph" {...props}></Icon>
