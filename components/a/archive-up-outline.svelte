<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzzw40e_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzzw40e_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-up-outline" {...props}></Icon>
