<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1mu-v3fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l1mu-v3fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-minimalistic-outline" {...props}></Icon>
