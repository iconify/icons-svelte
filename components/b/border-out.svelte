<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at_to3c-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at_to3c-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:border-out" {...props}></Icon>
