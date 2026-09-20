<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwvt3-eti.css';
import '../../css/y/ybcb2abco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvt3-eti"/><path class="ybcb2abco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cat-line" {...props}></Icon>
