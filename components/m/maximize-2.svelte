<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkfjhxory.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkfjhxory"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:maximize-2" {...props}></Icon>
