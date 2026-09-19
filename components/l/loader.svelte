<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbdpl6b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbdpl6b3n"><animateTransform attributeName="transform" attributeType="XML" dur="560ms" from="0,12,12" repeatCount="indefinite" to="360,12,12" type="rotate"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:loader" {...props}></Icon>
