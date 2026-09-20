<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y29dp-xoh.css';
import '../../css/n/n_blzqpck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y29dp-xoh"/><path class="n_blzqpck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plaaylist-minimalistic-bold" {...props}></Icon>
