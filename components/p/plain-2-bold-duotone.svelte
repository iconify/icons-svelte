<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgdh1dbhf.css';
import '../../css/p/pds7e2php.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgdh1dbhf"/><path class="pds7e2php"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plain-2-bold-duotone" {...props}></Icon>
