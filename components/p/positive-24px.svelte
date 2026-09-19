<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_emfbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae_emfbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:positive-24px" {...props}></Icon>
