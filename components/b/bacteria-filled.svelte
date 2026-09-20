<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h57ma544u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h57ma544u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bacteria-filled" {...props}></Icon>
