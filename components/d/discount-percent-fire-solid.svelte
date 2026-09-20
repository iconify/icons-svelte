<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9r9-qbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g9r9-qbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:discount-percent-fire-solid" {...props}></Icon>
