<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfnunqf6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfnunqf6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:order" {...props}></Icon>
