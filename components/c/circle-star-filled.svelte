<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaugexbvp.css';
import '../../css/k/k1bhl7bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaugexbvp"/><path clip-rule="evenodd" class="k1bhl7bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-star-filled" {...props}></Icon>
