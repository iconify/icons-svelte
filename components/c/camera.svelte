<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qrj6e5hdx.css';
import '../../css/c/cs-7h8fej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qrj6e5hdx"/><path class="cs-7h8fej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:camera" {...props}></Icon>
