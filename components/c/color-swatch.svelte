<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wwci4obui.css';
import '../../css/a/ar7v4zcbf.css';
import '../../css/m/mv28m9o7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwci4obui"/><path class="ar7v4zcbf"/><path class="mv28m9o7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:color-swatch" {...props}></Icon>
