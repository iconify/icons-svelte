<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo1-5mpqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":62,"height":24};
const content = `<path clip-rule="evenodd" class="qo1-5mpqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:arc-light" {...props}></Icon>
