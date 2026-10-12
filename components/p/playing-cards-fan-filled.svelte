<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2wfmvmec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2wfmvmec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:playing-cards-fan-filled" {...props}></Icon>
