<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng2ie-b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng2ie-b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:left-two-headed-line" {...props}></Icon>
