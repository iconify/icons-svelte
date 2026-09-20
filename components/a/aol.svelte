<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odmwx1c-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odmwx1c-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aol" {...props}></Icon>
