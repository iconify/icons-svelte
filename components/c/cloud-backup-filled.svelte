<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cltq9j6ti.css';
import '../../css/q/qfntjihwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cltq9j6ti"/><path class="qfntjihwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-backup-filled" {...props}></Icon>
