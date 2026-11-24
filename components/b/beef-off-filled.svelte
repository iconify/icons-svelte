<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsujivkiy.css';
import '../../css/v/vo9bl5pgd.css';
import '../../css/t/tz7299b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vsujivkiy"/><path class="vo9bl5pgd"/><path class="tz7299b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:beef-off-filled" {...props}></Icon>
