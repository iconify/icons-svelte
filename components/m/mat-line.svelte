<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdpu8s45u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdpu8s45u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mat-line" {...props}></Icon>
