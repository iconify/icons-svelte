<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slsyuwjqx.css';
import '../../css/y/yd2zepbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slsyuwjqx"/><path clip-rule="evenodd" class="yd2zepbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:css-fill" {...props}></Icon>
