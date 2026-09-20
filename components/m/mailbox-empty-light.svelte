<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/outf-abwk.css';
import '../../css/g/gd4eslbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="outf-abwk"/><path class="gd4eslbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:mailbox-empty-light" {...props}></Icon>
