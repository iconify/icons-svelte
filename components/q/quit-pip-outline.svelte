<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns7rrrbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ns7rrrbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-pip-outline" {...props}></Icon>
