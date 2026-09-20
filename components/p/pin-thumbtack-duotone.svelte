<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu1k7ld7a.css';
import '../../css/n/n41378bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu1k7ld7a"/><path clip-rule="evenodd" class="n41378bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pin-thumbtack-duotone" {...props}></Icon>
