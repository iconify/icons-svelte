<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss6rcc_ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ss6rcc_ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:password-alt-filled" {...props}></Icon>
