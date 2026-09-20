<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsrq7dtpz.css';
import '../../css/o/oto4ucbif.css';
import '../../css/i/iek1ggn7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsrq7dtpz"/><path class="oto4ucbif"/><path class="iek1ggn7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:envelope-at" {...props}></Icon>
