<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrnz5ebwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrnz5ebwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-right3" {...props}></Icon>
