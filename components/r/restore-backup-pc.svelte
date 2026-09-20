<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mij6dpb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mij6dpb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:restore-backup-pc" {...props}></Icon>
