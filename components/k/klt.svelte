<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coidrp9ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="coidrp9ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:klt" {...props}></Icon>
