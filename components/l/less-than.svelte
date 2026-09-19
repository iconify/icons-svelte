<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7607mb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="g7607mb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:less-than" {...props}></Icon>
