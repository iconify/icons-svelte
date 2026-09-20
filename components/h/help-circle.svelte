<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9i0_1j9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l9i0_1j9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:help-circle" {...props}></Icon>
