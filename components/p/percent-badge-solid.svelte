<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg4id_vou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eg4id_vou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:percent-badge-solid" {...props}></Icon>
