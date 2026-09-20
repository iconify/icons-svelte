<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9148sb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9148sb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-center-line" {...props}></Icon>
