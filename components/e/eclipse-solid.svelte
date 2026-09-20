<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw7a4lb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw7a4lb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:eclipse-solid" {...props}></Icon>
