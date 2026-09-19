<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntw-pqr2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntw-pqr2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-up-right-solid" {...props}></Icon>
