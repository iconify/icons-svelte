<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc0bmzbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc0bmzbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pendant-devote-three-solid" {...props}></Icon>
