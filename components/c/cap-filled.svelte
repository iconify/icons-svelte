<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niy3wwbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="niy3wwbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cap-filled" {...props}></Icon>
