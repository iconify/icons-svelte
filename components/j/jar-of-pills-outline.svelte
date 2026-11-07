<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvy-dbcdt.css';
import '../../css/e/ebdqu7z2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvy-dbcdt"/><path clip-rule="evenodd" class="ebdqu7z2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:jar-of-pills-outline" {...props}></Icon>
