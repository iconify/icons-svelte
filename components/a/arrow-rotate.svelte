<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5jxckb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5jxckb5q"><animateTransform attributeName="transform" attributeType="XML" dur="5s" from="360 12 12" repeatCount="indefinite" to="0 12 12" type="rotate"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:arrow-rotate" {...props}></Icon>
