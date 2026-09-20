<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7130egzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7130egzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:laptop" {...props}></Icon>
