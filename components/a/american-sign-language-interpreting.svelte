<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk7fr0_yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yk7fr0_yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:american-sign-language-interpreting" {...props}></Icon>
