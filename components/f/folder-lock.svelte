<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uecsehbiq.css';
import '../../css/s/s9ro2bzzp.css';
import '../../css/l/ll5_hob1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uecsehbiq"/><path clip-rule="evenodd" class="s9ro2bzzp"/><path clip-rule="evenodd" class="ll5_hob1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-lock" {...props}></Icon>
