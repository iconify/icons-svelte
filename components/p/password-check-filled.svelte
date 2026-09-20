<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y70-_76-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y70-_76-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:password-check-filled" {...props}></Icon>
