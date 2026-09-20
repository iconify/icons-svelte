<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egxi5i7oe.css';
import '../../css/e/e8uoipb2s.css';
import '../../css/i/i71zrdbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egxi5i7oe"/><path class="e8uoipb2s"/><path clip-rule="evenodd" class="i71zrdbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:paper-clock" {...props}></Icon>
