<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbdlp1bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbdlp1bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lodash" {...props}></Icon>
