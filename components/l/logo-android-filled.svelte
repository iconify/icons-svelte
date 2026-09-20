<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdkk788_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdkk788_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-android-filled" {...props}></Icon>
