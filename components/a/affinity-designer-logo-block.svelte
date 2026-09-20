<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk6g9lbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wk6g9lbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:affinity-designer-logo-block" {...props}></Icon>
