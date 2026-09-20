<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3y9ae9qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3y9ae9qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kalilinux" {...props}></Icon>
