<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvxsebk6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvxsebk6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:aim-logo-block" {...props}></Icon>
