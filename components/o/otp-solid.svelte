<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyystr3mw.css';
import '../../css/k/ko29mcbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hyystr3mw"/><path clip-rule="evenodd" class="ko29mcbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:otp-solid" {...props}></Icon>
