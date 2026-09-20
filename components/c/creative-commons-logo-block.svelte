<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd49lac2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qd49lac2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:creative-commons-logo-block" {...props}></Icon>
