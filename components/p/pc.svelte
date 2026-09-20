<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-7h8fb2z.css';
import '../../css/r/r21n4gx1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-7h8fb2z"/><path class="r21n4gx1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pc" {...props}></Icon>
