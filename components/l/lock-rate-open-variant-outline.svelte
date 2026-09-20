<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo8123eqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo8123eqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lock-rate-open-variant-outline" {...props}></Icon>
