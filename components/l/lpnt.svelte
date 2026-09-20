<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5xz9zb8a.css';
import '../../css/q/q2qrt1hqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5xz9zb8a"/><path clip-rule="evenodd" class="q2qrt1hqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lpnt" {...props}></Icon>
