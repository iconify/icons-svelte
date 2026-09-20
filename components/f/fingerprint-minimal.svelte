<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qu3o-gbgt.css';
import '../../css/h/h4xfh84tu.css';
import '../../css/m/mbaw2jbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qu3o-gbgt"/><path class="h4xfh84tu"/><path class="mbaw2jbyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:fingerprint-minimal" {...props}></Icon>
