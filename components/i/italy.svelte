<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9cl-boot.css';
import '../../css/a/apvpf298a.css';
import '../../css/b/bjo519b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="l9cl-boot"/><path class="apvpf298a"/><path class="bjo519b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:italy" {...props}></Icon>
