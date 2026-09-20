<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbjzahddm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbjzahddm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:help-question-network-bold" {...props}></Icon>
