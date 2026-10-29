<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rus3__a3u.css';
import '../../css/c/cu3aa_zia.css';
import '../../css/s/sx4nfqbeb.css';
import '../../css/r/rc8wxv_dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rus3__a3u wm-k"/><path class="cu3aa_zia wm-k"/><path class="sx4nfqbeb wm-k"/><path class="rc8wxv_dq wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:folder-search" {...props}></Icon>
