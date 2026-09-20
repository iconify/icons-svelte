<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am28lx2fj.css';
import '../../css/n/ncr5l6peb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am28lx2fj"/><path class="ncr5l6peb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-dublicate-duotone" {...props}></Icon>
