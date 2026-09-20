<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi105ybas.css';
import '../../css/c/cp_8-04cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xi105ybas"/><path class="cp_8-04cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:meetup-logo-solid" {...props}></Icon>
