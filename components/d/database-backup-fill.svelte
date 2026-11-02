<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad1kgub1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad1kgub1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:database-backup-fill" {...props}></Icon>
