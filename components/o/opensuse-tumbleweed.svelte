<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ias-elkyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ias-elkyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opensuse-tumbleweed" {...props}></Icon>
