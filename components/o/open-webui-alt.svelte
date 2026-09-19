<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp00o5b7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp00o5b7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:open-webui-alt" {...props}></Icon>
