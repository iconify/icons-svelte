<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdqpw2bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdqpw2bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-cloud-filled" {...props}></Icon>
