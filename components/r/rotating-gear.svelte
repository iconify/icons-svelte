<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo2pqcc3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo2pqcc3v"><animateTransform attributeName="transform" attributeType="XML" dur="10s" from="0 12 12" repeatCount="indefinite" to="360 12 12" type="rotate"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:rotating-gear" {...props}></Icon>
