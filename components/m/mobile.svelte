<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc7d6ubha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc7d6ubha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mobile" {...props}></Icon>
