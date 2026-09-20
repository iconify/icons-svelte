<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejeef6-rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejeef6-rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-wrap-inline" {...props}></Icon>
