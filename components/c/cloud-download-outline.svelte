<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tahbz4kss.css';
import '../../css/n/n6c26r64u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tahbz4kss"/><path clip-rule="evenodd" class="n6c26r64u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cloud-download-outline" {...props}></Icon>
