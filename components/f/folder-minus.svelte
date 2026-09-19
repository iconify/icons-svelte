<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z18oahqfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z18oahqfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:folder-minus" {...props}></Icon>
