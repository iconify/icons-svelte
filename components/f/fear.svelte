<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnra-dbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnra-dbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fear" {...props}></Icon>
