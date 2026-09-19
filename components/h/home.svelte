<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6u2o4t9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6u2o4t9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:home" {...props}></Icon>
